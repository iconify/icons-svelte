<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyi-blxwk.css';
import '../../css/i/iw8xtjb4w.css';
import '../../css/c/c18_ysapx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zyi-blxwk"/><path class="iw8xtjb4w"/><path class="c18_ysapx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:taiga-dark" {...props}></Icon>
