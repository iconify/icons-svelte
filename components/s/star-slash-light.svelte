<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn-x8ouzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wn-x8ouzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:star-slash-light" {...props}></Icon>
