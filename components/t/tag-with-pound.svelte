<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ureuy2bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ureuy2bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tag-with-pound" {...props}></Icon>
