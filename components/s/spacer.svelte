<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csi3jmbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="csi3jmbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:spacer" {...props}></Icon>
