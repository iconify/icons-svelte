<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rzkg9v93r.css';
import '../../css/i/i56olo2az.css';
import '../../css/n/npn8u77dk.css';
import '../../css/a/apvj7jbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rzkg9v93r"/><circle class="i56olo2az"/><path class="npn8u77dk"/><path class="apvj7jbhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sickbed" {...props}></Icon>
