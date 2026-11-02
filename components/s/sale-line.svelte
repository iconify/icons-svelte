<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl2f5u--n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl2f5u--n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sale-line" {...props}></Icon>
