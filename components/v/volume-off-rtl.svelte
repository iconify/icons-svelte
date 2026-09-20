<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sydqsyb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sydqsyb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:volume-off-rtl" {...props}></Icon>
