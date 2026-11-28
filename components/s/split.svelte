<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj9x87k_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj9x87k_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:split" {...props}></Icon>
