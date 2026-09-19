<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xh3xwnbnn.css';
import '../../css/c/c3fqsnlyc.css';
import '../../css/d/dgjqt8bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xh3xwnbnn"/><path class="c3fqsnlyc"/><path class="dgjqt8bah"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:uterus" {...props}></Icon>
