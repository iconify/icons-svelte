<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs3-wob5i.css';
import '../../css/a/a3mwubgrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs3-wob5i"/><path class="a3mwubgrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xrsh-light" {...props}></Icon>
