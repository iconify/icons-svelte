<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/madko4bbz.css';
import '../../css/f/fgkwccyip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="madko4bbz"/><path class="fgkwccyip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-left-down-bold-duotone" {...props}></Icon>
