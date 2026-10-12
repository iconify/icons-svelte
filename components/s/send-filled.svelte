<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmexh2bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmexh2bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:send-filled" {...props}></Icon>
