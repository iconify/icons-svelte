<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pe2y8tblj.css';
import '../../css/j/jpauy220p.css';
import '../../css/z/zw_tipbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="pe2y8tblj"/><circle class="jpauy220p"/><path class="zw_tipbom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-minus-circle-duotone" {...props}></Icon>
