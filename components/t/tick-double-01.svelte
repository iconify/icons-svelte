<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoo_40b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoo_40b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tick-double-01" {...props}></Icon>
