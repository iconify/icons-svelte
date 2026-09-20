<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k80kg2mvy.css';
import '../../css/o/o_xxtf8jm.css';
import '../../css/p/p397vciec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="k80kg2mvy"/><path class="o_xxtf8jm"/><path class="p397vciec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:walking-line-duotone" {...props}></Icon>
