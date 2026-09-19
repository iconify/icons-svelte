<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2u2u_bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2u2u_bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:solar-energy-filled" {...props}></Icon>
