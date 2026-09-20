<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unc2embyj.css';
import '../../css/i/ic08mpydp.css';
import '../../css/i/i7s8v2b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="unc2embyj"><path class="ic08mpydp"/><circle class="i7s8v2b0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-duotone-line" {...props}></Icon>
