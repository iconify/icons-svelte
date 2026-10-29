<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4bph3b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4bph3b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ticket-solid" {...props}></Icon>
