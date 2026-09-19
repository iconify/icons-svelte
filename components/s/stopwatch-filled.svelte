<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kykar5ibp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kykar5ibp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:stopwatch-filled" {...props}></Icon>
