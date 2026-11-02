<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svs_3lbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svs_3lbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-add-line" {...props}></Icon>
