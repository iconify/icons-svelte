<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5cg8fb9r.css';
import '../../css/q/qgymvr2-d.css';
import '../../css/y/ytep3bcxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="qgymvr2-d"/><path class="ytep3bcxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:thin" {...props}></Icon>
