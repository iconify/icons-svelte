<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6velp7dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6velp7dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shopping-basket-gloss" {...props}></Icon>
