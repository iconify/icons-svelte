<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/cwkyo5bfm.css';
import '../../css/v/vca6n0zbn.css';
import '../../css/t/tm3o10moh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="cwkyo5bfm"/><path class="vca6n0zbn"/><circle class="tm3o10moh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sunset" {...props}></Icon>
