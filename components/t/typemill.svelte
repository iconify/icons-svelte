<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqu2_e4mu.css';
import '../../css/r/r698ifziu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="pqu2_e4mu"/><path class="r698ifziu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typemill" {...props}></Icon>
