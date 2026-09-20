<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc87u0btn.css';
import '../../css/f/fs_fwv3jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc87u0btn"/><path class="fs_fwv3jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:walkman-player" {...props}></Icon>
