<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu2lkfbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mu2lkfbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:test-step" {...props}></Icon>
