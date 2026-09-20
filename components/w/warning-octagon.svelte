<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny2kalc0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny2kalc0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-octagon" {...props}></Icon>
