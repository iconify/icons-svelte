<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4q-webeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d4q-webeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:star-add" {...props}></Icon>
