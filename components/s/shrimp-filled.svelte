<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjna77bsx.css';
import '../../css/z/z02gnab-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjna77bsx"/><path clip-rule="evenodd" class="z02gnab-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shrimp-filled" {...props}></Icon>
