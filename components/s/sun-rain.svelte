<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw0p3-b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw0p3-b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-rain" {...props}></Icon>
