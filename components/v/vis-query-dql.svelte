<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8s6xvu0y.css';
import '../../css/a/av8fdd_xa.css';
import '../../css/r/rs66qrblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w8s6xvu0y"/><path class="av8fdd_xa"/><path clip-rule="evenodd" class="rs66qrblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-query-dql" {...props}></Icon>
