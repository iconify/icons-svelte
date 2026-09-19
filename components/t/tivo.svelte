<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjks_m-az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjks_m-az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tivo" {...props}></Icon>
