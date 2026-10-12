<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dak59cc1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dak59cc1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:scooter-filled" {...props}></Icon>
