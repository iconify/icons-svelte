<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztxiwhgno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztxiwhgno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:saturation-filled" {...props}></Icon>
