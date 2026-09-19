<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtyx4x3lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qtyx4x3lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:shift" {...props}></Icon>
