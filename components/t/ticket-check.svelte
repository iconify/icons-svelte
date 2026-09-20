<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0u8-zwcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0u8-zwcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:ticket-check" {...props}></Icon>
