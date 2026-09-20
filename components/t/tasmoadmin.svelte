<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp_egdbju.css';
import '../../css/n/nxo71mbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="xp_egdbju"/><path class="nxo71mbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tasmoadmin" {...props}></Icon>
