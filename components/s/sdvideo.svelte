<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i13rn9bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="i13rn9bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sdvideo" {...props}></Icon>
