<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg0z4wbgl.css';
import '../../css/g/gkrl9j4we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0z4wbgl"/><path clip-rule="evenodd" class="gkrl9j4we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-small-bold-duotone" {...props}></Icon>
