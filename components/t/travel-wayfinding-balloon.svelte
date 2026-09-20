<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxpo9jkdm.css';
import '../../css/x/xg28s7bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zxpo9jkdm"/><path class="xg28s7bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:travel-wayfinding-balloon" {...props}></Icon>
