<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk1u7ubxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk1u7ubxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:substack-fill" {...props}></Icon>
