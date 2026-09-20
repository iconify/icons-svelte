<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unc2embyj.css';
import '../../css/x/x8o5_8bro.css';
import '../../css/s/spr08kbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="unc2embyj"><circle class="x8o5_8bro"/><path class="spr08kbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-add-alt-duotone-line" {...props}></Icon>
