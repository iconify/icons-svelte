<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi25mkbtf.css';
import '../../css/m/mpywkgvrr.css';
import '../../css/z/zi6a9qsdc.css';
import '../../css/o/o5eicpnmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bi25mkbtf"/><path class="mpywkgvrr"/><path class="zi6a9qsdc"/><path class="o5eicpnmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:satellite-bold-duotone" {...props}></Icon>
