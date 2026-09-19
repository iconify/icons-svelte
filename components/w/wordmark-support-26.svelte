<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u81g_fbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":82,"height":26};
const content = `<path class="u81g_fbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-support-26" {...props}></Icon>
