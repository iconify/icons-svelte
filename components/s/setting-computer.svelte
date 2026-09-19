<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/h/hq5j0kbho.css';
import '../../css/a/ah51uhl8u.css';
import '../../css/i/iug4c3bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="hq5j0kbho"/><circle class="ah51uhl8u"/><path class="iug4c3bzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:setting-computer" {...props}></Icon>
