<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3hwjbczf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3hwjbczf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transaction-bitcoin" {...props}></Icon>
