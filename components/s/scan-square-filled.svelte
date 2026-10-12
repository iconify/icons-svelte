<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_tbmpogi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_tbmpogi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scan-square-filled" {...props}></Icon>
