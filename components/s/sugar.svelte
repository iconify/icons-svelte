<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7i33_fpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7i33_fpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sugar" {...props}></Icon>
