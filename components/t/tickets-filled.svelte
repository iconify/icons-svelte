<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi4k0l1-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi4k0l1-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tickets-filled" {...props}></Icon>
