<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8_t08f2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8_t08f2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:test-tubes" {...props}></Icon>
