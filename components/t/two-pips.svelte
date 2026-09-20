<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik25qgb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ik25qgb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-pips" {...props}></Icon>
