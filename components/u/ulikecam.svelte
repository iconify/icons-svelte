<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly6jl_bkj.css';
import '../../css/g/gb7t1obix.css';
import '../../css/c/ca-lc-jmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ly6jl_bkj"><path class="gb7t1obix"/><path class="ca-lc-jmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:ulikecam" {...props}></Icon>
