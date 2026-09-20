<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saz8lgmuq.css';
import '../../css/p/pb0vhv85n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="saz8lgmuq"/><path class="pb0vhv85n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:settings" {...props}></Icon>
