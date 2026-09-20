<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrtx0ebqp.css';
import '../../css/a/a74kpfbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zrtx0ebqp"/><path class="a74kpfbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tradetally" {...props}></Icon>
