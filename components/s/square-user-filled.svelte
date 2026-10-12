<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgl37rgry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgl37rgry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-user-filled" {...props}></Icon>
