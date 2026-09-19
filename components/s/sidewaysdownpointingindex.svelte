<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwany8eak.css';
import '../../css/l/laefk-_jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwany8eak"/><path class="laefk-_jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:sidewaysdownpointingindex" {...props}></Icon>
