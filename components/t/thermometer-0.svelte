<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai5bd-qzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ai5bd-qzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:thermometer-0" {...props}></Icon>
