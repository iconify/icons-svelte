<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke_bx8-uq.css';
import '../../css/m/mqx34y6qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="ke_bx8-uq"/><rect class="mqx34y6qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rows-filled" {...props}></Icon>
