<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddz2_obsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ddz2_obsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:step-shared-insert" {...props}></Icon>
