<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo8q8sbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo8q8sbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:upload-3-line" {...props}></Icon>
