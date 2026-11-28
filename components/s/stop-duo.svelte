<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6yvi_chi.css';
import '../../css/t/t8i6bfbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6yvi_chi secondary"/><path class="primary t8i6bfbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stop-duo" {...props}></Icon>
