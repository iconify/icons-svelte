<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e13iwsa6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":26};
const content = `<path class="e13iwsa6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-bold-suite-26" {...props}></Icon>
