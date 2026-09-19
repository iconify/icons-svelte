<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8attu2qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8attu2qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vac-mop" {...props}></Icon>
