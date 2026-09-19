<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vkcj4bcdm.css';
import '../../css/r/rer8mf95d.css';
import '../../css/m/mdurccb4e.css';
import '../../css/b/b6vpmabbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vkcj4bcdm"/><path class="rer8mf95d"/><path class="mdurccb4e"/><path class="b6vpmabbz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:volkswagen" {...props}></Icon>
