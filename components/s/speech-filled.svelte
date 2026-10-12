<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu9cqub2t.css';
import '../../css/u/uusba_vxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu9cqub2t"/><path class="uusba_vxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:speech-filled" {...props}></Icon>
