<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r888i_z2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r888i_z2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ticket-fill" {...props}></Icon>
