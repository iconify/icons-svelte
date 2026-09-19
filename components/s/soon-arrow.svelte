<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv-j_tzgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pv-j_tzgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:soon-arrow" {...props}></Icon>
