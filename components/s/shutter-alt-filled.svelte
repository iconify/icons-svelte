<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzm0xyeiv.css';
import '../../css/x/xs08igbmf.css';
import '../../css/x/xaa-pclmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzm0xyeiv"/><path class="xs08igbmf"/><path class="xaa-pclmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shutter-alt-filled" {...props}></Icon>
