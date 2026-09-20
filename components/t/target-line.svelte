<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib68pbbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib68pbbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:target-line" {...props}></Icon>
