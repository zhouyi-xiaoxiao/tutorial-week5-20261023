# Mathematics tutorials: questions and key points

**Group 07 · 5–6 November 2026 · A4 print version**

This handout is for tutorial preparation and discussion. Check Blackboard for the official problem-sheet wording and submission instructions.

## 1. Introduction to Pure Mathematics

**Thursday 5 November 2026, 09:00–10:00**  
**Room:** PRIORY RD CMPLX F BLK 3F11

### Key points

- **Image:** f(A) = { f(a) : a ∈ A }.
- **Pre-image:** f⁻¹(B) = { a ∈ A : f(a) ∈ B }. A pre-image is a subset of the domain.
- **Injective:** f(a₁) = f(a₂) ⇒ a₁ = a₂.
- **Surjective:** every element of the codomain has at least one pre-image.
- **Bijective:** injective and surjective.
- Always state the **domain and codomain** before classifying a function.
- For an abstract proof, use the definitions. For a counterexample, verify the domain, codomain, and the failed property.

### Questions

1. For each map, decide whether it is injective, surjective, bijective, or neither. Give a definition-based justification.

   a. f: ℝ → ℝ, f(x) = 2x − 3.

   b. g: ℝ → ℝ, g(x) = x².

   c. h: ℝ → [0, ∞), h(x) = x².

2. Let p: ℝ → ℝ, p(x) = x² − 1.

   a. Find p([−1, 2]).

   b. Find p⁻¹([0, 3]).

   c. Explain why the answers in (a) and (b) are different kinds of sets.

3. Let A and B be sets and f: A → B.

   a. Write the definitions of injective and surjective in your own words and in symbols.

   b. If f and g are injective, prove that g ∘ f is injective.

   c. Give a concrete function that is surjective but not injective, and explain exactly where injectivity fails.

4. **PS5 discussion focus.** Choose two peer submissions. For each one, record:

   - one step where the argument is correct and clearly explained;
   - one step where a definition, domain/codomain, or justification should be made more explicit;
   - one short question you would ask the author.

## 2. Linear Algebra

**Friday 6 November 2026, 09:00–10:00**  
**Room:** FRY BLDG G.14

### Key points

- **Span:** all linear combinations of a set of vectors.
- **Linear independence:** the only linear combination giving the zero vector has all coefficients zero.
- **Basis:** a linearly independent spanning set.
- **Dimension:** the number of vectors in a basis.
- **Subspace:** check that the set contains zero and is closed under addition and scalar multiplication.
- **Sum and intersection:** X + Y = {x + y : x ∈ X, y ∈ Y}, and dim(X + Y) = dim X + dim Y − dim(X ∩ Y).
- **Row reduction:** pivot columns identify rank; free variables describe the null space.
- **Rank–nullity:** for T: ℝⁿ → ℝᵐ, dim(ker T) + dim(im T) = n.

### Questions

1. Let V = { (x, y, z, x + iy) ∈ ℂ⁴ : x, y, z ∈ ℂ }. Show that V is a complex subspace of ℂ⁴. Find a basis and dim V.

2. Let X, Y ⊆ ℝⁿ be subspaces with dim X = m and dim Y = k.

   a. Is dim(X + Y) = m + k always true? Explain.

   b. State and justify the correct dimension formula.

   c. Give one example where the intersection is trivial and one where it is not.

3. Decide whether the following vectors in ℝ³ are linearly independent:

   v₁ = (1, 2, −1),   v₂ = (1, 1, 1),   v₃ = (0, 1, −2).

   Use a homogeneous linear system or row reduction, and state whether they form a basis of ℝ³.

4. Find the null space and rank of the matrix A with rows (1, 2, 1), (2, 4, 2), (1, 1, 0). Give a basis for the null space and explain how the number of pivots gives the rank.

5. Let T: ℝ³ → ℝ² be defined by T(x, y, z) = (x + y, y + z). Find ker T, im T, the rank, and the nullity. Check rank–nullity.

6. For one of Questions 1–5, write a complete solution in a form another student could check line by line. Mark where you use a definition, a theorem, or a row operation.

## Quick self-check before class

- Have I written the domain and codomain for every function question?
- Can I distinguish an image from a pre-image?
- Can I prove independence by starting with a linear combination equal to zero?
- Can I explain why a proposed basis both spans and is independent?
- Can I use the intersection term in the dimension formula?
- Can I identify pivots, free variables, rank, and nullity after row reduction?
