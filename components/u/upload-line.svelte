<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mehrf5bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mehrf5bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:upload-line" {...props}></Icon>
