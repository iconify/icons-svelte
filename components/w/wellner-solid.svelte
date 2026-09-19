<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1080knip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1080knip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wellner-solid" {...props}></Icon>
