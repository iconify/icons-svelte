<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2uf-660j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2uf-660j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:watch-status-filled" {...props}></Icon>
