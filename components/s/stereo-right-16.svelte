<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r97kr0boe.css';
import '../../css/w/wzy28rbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r97kr0boe"/><path clip-rule="evenodd" class="wzy28rbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:stereo-right-16" {...props}></Icon>
