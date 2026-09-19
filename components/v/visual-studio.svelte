<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcrbt8b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xcrbt8b4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:visual-studio" {...props}></Icon>
