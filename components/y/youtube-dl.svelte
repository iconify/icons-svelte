<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h683xnbcm.css';
import '../../css/i/ima57ac7n.css';
import '../../css/m/mdfbtzb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h683xnbcm"/><circle class="ima57ac7n"/><path class="mdfbtzb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtube-dl" {...props}></Icon>
