<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er9_2_bjd.css';
import '../../css/v/vg928d-qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er9_2_bjd"/><path class="vg928d-qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-dot-bold-duotone" {...props}></Icon>
