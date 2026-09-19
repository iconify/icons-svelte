<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kg1w76bky.css';
import '../../css/g/g7hc3h9gh.css';
import '../../css/x/xa06vonbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="kg1w76bky"/><path class="g7hc3h9gh"/><path class="xa06vonbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:signal-strength" {...props}></Icon>
