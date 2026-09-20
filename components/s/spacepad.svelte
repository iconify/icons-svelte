<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psk9w-asf.css';
import '../../css/m/mqh2rrbti.css';
import '../../css/s/sb8cqvbau.css';
import '../../css/i/iypdzxlxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="psk9w-asf"/><path class="mqh2rrbti"/><path class="sb8cqvbau"/><circle class="iypdzxlxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spacepad" {...props}></Icon>
