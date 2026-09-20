<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5jp2kbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5jp2kbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:setting3-filled" {...props}></Icon>
