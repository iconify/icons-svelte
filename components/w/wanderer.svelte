<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxwpwpbas.css';
import '../../css/d/dqt391b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxwpwpbas"/><path class="dqt391b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wanderer" {...props}></Icon>
