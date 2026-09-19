<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/e/e4sdhbc-x.css';
import '../../css/h/h-lp_vb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="e4sdhbc-x"/><path class="h-lp_vb0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:theater" {...props}></Icon>
