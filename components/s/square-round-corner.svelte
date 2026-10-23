<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z23dvnbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z23dvnbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-round-corner" {...props}></Icon>
