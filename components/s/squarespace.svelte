<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfoildnck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="pfoildnck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:squarespace" {...props}></Icon>
