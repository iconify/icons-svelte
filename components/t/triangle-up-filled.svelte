<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd7gesedg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yd7gesedg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:triangle-up-filled" {...props}></Icon>
