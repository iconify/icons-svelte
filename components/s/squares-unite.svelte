<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in2qn8b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in2qn8b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:squares-unite" {...props}></Icon>
