<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cbzvvub2o.css';
import '../../css/e/eib6gdcac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle transform="matrix(0 -1 -1 0 20 19)" class="cbzvvub2o"/><path class="eib6gdcac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sign-in-circle-duotone" {...props}></Icon>
