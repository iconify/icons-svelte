<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iib28-19w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iib28-19w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:teeth-open" {...props}></Icon>
