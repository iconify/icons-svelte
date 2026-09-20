<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ape36fnyv.css';
import '../../css/x/xlr8dz81c.css';
import '../../css/h/h1_u2g9co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ape36fnyv"/><path class="xlr8dz81c"/><circle class="h1_u2g9co"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:table-settings" {...props}></Icon>
