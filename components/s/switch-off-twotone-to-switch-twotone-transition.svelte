<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psp_wn.css';
import '../../css/y/ydovum.css';
import '../../css/d/ds-pxa.css';
import '../../css/c/cx-from-7px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psp_wn ydovum"/><circle class="ds-pxa ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:switch-off-twotone-to-switch-twotone-transition" {...props}></Icon>
