<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kje3rqtmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="kje3rqtmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:swipedown" {...props}></Icon>
