<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dtmozb3dv.css';
import '../../css/k/ky47cdc5i.css';
import '../../css/c/cwk6upbkl.css';
import '../../css/h/hlz_d0lwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dtmozb3dv"/><path class="ky47cdc5i"/><path class="cwk6upbkl"/><path class="hlz_d0lwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:share-circle-linear" {...props}></Icon>
