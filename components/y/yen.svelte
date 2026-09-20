<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e79hwtb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="e79hwtb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:yen" {...props}></Icon>
