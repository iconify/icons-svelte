<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0dgp1bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0dgp1bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:virtual-host-manager" {...props}></Icon>
