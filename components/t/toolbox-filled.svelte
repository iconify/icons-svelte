<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlj9jxb_e.css';
import '../../css/o/owo49jf1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlj9jxb_e"/><path clip-rule="evenodd" class="owo49jf1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:toolbox-filled" {...props}></Icon>
