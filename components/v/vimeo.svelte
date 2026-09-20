<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv4v6pbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4v6pbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vimeo" {...props}></Icon>
