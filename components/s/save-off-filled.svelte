<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxm7zcclr.css';
import '../../css/s/sk2-r8bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xxm7zcclr"/><path class="sk2-r8bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-off-filled" {...props}></Icon>
