<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxg-_if6l.css';
import '../../css/z/zngdjrb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qxg-_if6l"/><path class="zngdjrb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:un-lock" {...props}></Icon>
