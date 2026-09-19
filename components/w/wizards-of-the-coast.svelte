<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svzk-5qxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="svzk-5qxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:wizards-of-the-coast" {...props}></Icon>
