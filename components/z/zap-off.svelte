<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm83-l12l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm83-l12l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:zap-off" {...props}></Icon>
