<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xqyp4q2de.css';
import '../../css/b/brqvdqb4k.css';
import '../../css/q/qiw5s9b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="xqyp4q2de"/><path class="brqvdqb4k"/><path class="qiw5s9b3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:transport" {...props}></Icon>
