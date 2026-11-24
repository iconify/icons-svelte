<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcc1i2lqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcc1i2lqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:stroke-width-filled" {...props}></Icon>
