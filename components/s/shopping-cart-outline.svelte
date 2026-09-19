<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3huzywhg.css';
import '../../css/a/af8o1jbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3huzywhg"/><path class="af8o1jbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:shopping-cart-outline" {...props}></Icon>
