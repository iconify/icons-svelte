<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uz4j7qb2v.css';
import '../../css/m/md286fbip.css';
import '../../css/m/mftkw4boq.css';
import '../../css/e/ej3f_vktx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="uz4j7qb2v"/><g class="md286fbip"><path class="mftkw4boq"/><path class="ej3f_vktx"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:yfi" {...props}></Icon>
