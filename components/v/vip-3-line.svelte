<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwyl4jeby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwyl4jeby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vip-3-line" {...props}></Icon>
