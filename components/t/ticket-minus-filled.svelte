<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzi2ayb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzi2ayb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ticket-minus-filled" {...props}></Icon>
