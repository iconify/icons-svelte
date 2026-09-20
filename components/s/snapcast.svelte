<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp49xnb5l.css';
import '../../css/w/wln7u9w6d.css';
import '../../css/d/d45omcbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="hp49xnb5l"/><path class="wln7u9w6d"/><path class="d45omcbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapcast" {...props}></Icon>
