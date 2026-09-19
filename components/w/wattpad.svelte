<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxdnurqzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxdnurqzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wattpad" {...props}></Icon>
