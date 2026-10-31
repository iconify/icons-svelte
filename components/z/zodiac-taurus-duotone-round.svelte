<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjmkdlb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjmkdlb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-taurus-duotone-round" {...props}></Icon>
