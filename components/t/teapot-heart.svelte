<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csb1qxakk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csb1qxakk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:teapot-heart" {...props}></Icon>
