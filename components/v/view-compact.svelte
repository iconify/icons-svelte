<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2om1_1xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i2om1_1xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:view-compact" {...props}></Icon>
