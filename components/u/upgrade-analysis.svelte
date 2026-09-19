<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq_b7uk2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vq_b7uk2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:upgrade-analysis" {...props}></Icon>
