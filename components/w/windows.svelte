<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dihi-wble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dihi-wble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:windows" {...props}></Icon>
