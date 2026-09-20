<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd83idj5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="qd83idj5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shortcode" {...props}></Icon>
