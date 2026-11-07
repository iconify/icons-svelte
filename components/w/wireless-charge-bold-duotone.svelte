<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oso782buv.css';
import '../../css/i/ik4h_zthb.css';
import '../../css/l/lwh3p0k8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oso782buv"/><path class="ik4h_zthb"/><path class="lwh3p0k8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wireless-charge-bold-duotone" {...props}></Icon>
