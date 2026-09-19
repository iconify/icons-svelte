<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae6sq6hrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ae6sq6hrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:smile2" {...props}></Icon>
