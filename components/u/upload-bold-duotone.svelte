<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c26kd0bsp.css';
import '../../css/z/zebewq1gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c26kd0bsp"/><path clip-rule="evenodd" class="zebewq1gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-bold-duotone" {...props}></Icon>
