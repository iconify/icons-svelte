<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l26w1ybvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l26w1ybvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:xcode" {...props}></Icon>
