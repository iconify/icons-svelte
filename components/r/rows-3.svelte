<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjp272mmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjp272mmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rows-3" {...props}></Icon>
