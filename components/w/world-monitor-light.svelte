<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdofmibhs.css';
import '../../css/k/kcdmr56ch.css';
import '../../css/u/u8e9kpb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdofmibhs"/><path class="kcdmr56ch"/><circle class="u8e9kpb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:world-monitor-light" {...props}></Icon>
