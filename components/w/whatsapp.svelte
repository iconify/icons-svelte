<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qin0occ5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1600};
const content = `<path class="qin0occ5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:whatsapp" {...props}></Icon>
