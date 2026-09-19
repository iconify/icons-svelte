<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/ctq-00ygq.css';
import '../../css/o/o8x35cc1s.css';
import '../../css/j/jvsjkqbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ctq-00ygq"/><path class="o8x35cc1s"/><path class="jvsjkqbyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:seo-folder" {...props}></Icon>
