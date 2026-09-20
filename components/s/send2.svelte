<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo2nz1lwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo2nz1lwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:send2" {...props}></Icon>
