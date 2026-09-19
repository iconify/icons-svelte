<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vae5tl_vn.css';
import '../../css/t/tgxo-cukz.css';
import '../../css/u/u0z5bpiqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vae5tl_vn"/><circle class="tgxo-cukz"/><path class="u0z5bpiqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:timed-mail" {...props}></Icon>
