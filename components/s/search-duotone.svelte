<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ay5e68biv.css';
import '../../css/l/lk74elbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ay5e68biv"/><path class="lk74elbap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:search-duotone" {...props}></Icon>
