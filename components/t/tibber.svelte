<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0rrvtb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0rrvtb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tibber" {...props}></Icon>
