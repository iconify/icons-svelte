<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sds3d1box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sds3d1box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shirt-fill" {...props}></Icon>
