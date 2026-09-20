<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpoo19blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpoo19blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ticket-bold" {...props}></Icon>
