<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-p0k3n1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-p0k3n1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:skype" {...props}></Icon>
