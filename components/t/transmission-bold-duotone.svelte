<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw-szkbrd.css';
import '../../css/f/f96gcgbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw-szkbrd"/><path clip-rule="evenodd" class="f96gcgbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transmission-bold-duotone" {...props}></Icon>
