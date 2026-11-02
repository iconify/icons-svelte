<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ota4psolv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ota4psolv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sad-line" {...props}></Icon>
