<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc2_ucbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vc2_ucbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:volume-off-ltr" {...props}></Icon>
