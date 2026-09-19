<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/tu4qdd9vm.css';
import '../../css/l/lnotn3pcn.css';
import '../../css/r/r-m4ambab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="tu4qdd9vm"/><path class="lnotn3pcn"/><circle class="r-m4ambab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sleep-two" {...props}></Icon>
