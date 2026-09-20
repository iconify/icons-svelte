<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bkmy5cc1h.css';
import '../../css/c/ce3_ju4gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bkmy5cc1h"/><path class="ce3_ju4gd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-east-square-duotone" {...props}></Icon>
