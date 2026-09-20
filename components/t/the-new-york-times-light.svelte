<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yro5ksbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yro5ksbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-new-york-times-light" {...props}></Icon>
