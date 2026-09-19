<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sblito_hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sblito_hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:vimeo-square" {...props}></Icon>
