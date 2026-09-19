<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb4-vf7ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="fb4-vf7ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:wordpress" {...props}></Icon>
