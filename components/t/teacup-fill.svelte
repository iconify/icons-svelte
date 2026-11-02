<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no7_26bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no7_26bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:teacup-fill" {...props}></Icon>
