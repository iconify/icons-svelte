<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0l1cwbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x0l1cwbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sencho-light" {...props}></Icon>
