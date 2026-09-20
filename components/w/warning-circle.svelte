<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eqk_cmbqi.css';
import '../../css/m/mdh3hzb-o.css';
import '../../css/l/ll0qxj7eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><circle class="eqk_cmbqi"/><path class="mdh3hzb-o"/><circle class="ll0qxj7eq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:warning-circle" {...props}></Icon>
