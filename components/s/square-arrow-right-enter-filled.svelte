<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn5j5rbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn5j5rbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-arrow-right-enter-filled" {...props}></Icon>
