<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv2_z3-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv2_z3-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-number-0-filled" {...props}></Icon>
