<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygemgcbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1027,"height":1026};
const content = `<path class="ygemgcbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:watch" {...props}></Icon>
