<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psp_wn.css';
import '../../css/y/ydovum.css';
import '../../css/k/kjds8p.css';
import '../../css/c/cx-from-17px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psp_wn ydovum"/><circle class="kjds8p ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:switch-twotone-to-switch-off-twotone-transition" {...props}></Icon>
