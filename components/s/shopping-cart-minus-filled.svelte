<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pud5wbbsm.css';
import '../../css/p/pz991cbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pud5wbbsm"/><path class="pz991cbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shopping-cart-minus-filled" {...props}></Icon>
