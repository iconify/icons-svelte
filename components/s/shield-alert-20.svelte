<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkihj-w6g.css';
import '../../css/y/yttd9waod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkihj-w6g"/><path class="yttd9waod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-alert-20" {...props}></Icon>
