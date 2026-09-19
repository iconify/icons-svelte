<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wos-s-4gk.css';
import '../../css/r/rxfy9jprx.css';
import '../../css/h/h3hcrvkyu.css';
import '../../css/s/s4esdgbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="wos-s-4gk"/><path class="rxfy9jprx"/><path class="h3hcrvkyu"/><path class="s4esdgbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:two-triangles" {...props}></Icon>
