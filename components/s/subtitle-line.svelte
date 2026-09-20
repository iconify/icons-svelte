<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1o33v6nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1o33v6nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:subtitle-line" {...props}></Icon>
