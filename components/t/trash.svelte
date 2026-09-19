<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk1ioby0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk1ioby0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:trash" {...props}></Icon>
