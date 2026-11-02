<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trsk72z_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trsk72z_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:swimming-pool-fill" {...props}></Icon>
