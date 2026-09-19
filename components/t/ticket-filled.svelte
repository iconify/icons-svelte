<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuahm6pfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuahm6pfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ticket-filled" {...props}></Icon>
