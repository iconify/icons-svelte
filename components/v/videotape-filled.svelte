<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovu4icjzb.css';
import '../../css/v/vk_vtrrnl.css';
import '../../css/p/poade0yht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovu4icjzb"/><path clip-rule="evenodd" class="vk_vtrrnl"/><path class="poade0yht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:videotape-filled" {...props}></Icon>
