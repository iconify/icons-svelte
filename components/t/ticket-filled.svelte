<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-8t4ybdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-8t4ybdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ticket-filled" {...props}></Icon>
