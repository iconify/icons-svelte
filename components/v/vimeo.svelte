<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buth0fb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="buth0fb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:vimeo" {...props}></Icon>
