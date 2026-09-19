<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/gz8--lx8p.css';
import '../../css/m/mz340mupd.css';
import '../../css/y/yrx40bbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="gz8--lx8p"/><path class="mz340mupd"/><path class="yrx40bbij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:up-c" {...props}></Icon>
