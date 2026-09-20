<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwxl3xbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwxl3xbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sound-low-filled" {...props}></Icon>
