<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnqiikm4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="wnqiikm4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:truck" {...props}></Icon>
