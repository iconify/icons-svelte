<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_bllyb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_bllyb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vercel" {...props}></Icon>
