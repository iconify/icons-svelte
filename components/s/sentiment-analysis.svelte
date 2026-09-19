<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvt4d9b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wvt4d9b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:sentiment-analysis" {...props}></Icon>
