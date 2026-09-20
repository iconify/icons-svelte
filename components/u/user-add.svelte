<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl0smq5gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vl0smq5gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:user-add" {...props}></Icon>
