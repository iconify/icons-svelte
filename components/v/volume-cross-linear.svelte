<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c78l8sbth.css';
import '../../css/g/go0njccyz.css';
import '../../css/c/ccm11mbdl.css';
import '../../css/r/rsrhfac5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c78l8sbth"/><path class="go0njccyz"/><path class="ccm11mbdl"/><path class="rsrhfac5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-cross-linear" {...props}></Icon>
