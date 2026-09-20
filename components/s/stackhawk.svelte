<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mita9mefx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mita9mefx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:stackhawk" {...props}></Icon>
