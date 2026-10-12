<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkw_aib9x.css';
import '../../css/o/onixhkbxr.css';
import '../../css/u/umdfmcbpo.css';
import '../../css/a/a00b_rbme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pkw_aib9x"/><path class="onixhkbxr"/><path class="umdfmcbpo"/><path class="a00b_rbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:town-hall-48-bold" {...props}></Icon>
