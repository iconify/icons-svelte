<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dv179xopj.css';
import '../../css/w/wl0yr8bgj.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsUiFolderFamilyNegative0)" class="cuyn6tgcc"><path class="dv179xopj"/><path clip-rule="evenodd" class="wl0yr8bgj"/></g><defs><clipPath id="healthiconsUiFolderFamilyNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ui-folder-family-negative" {...props}></Icon>
