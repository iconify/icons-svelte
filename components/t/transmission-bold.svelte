<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4ba7dbhr.css';
import '../../css/m/mo2l0vb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4ba7dbhr"/><path class="mo2l0vb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transmission-bold" {...props}></Icon>
