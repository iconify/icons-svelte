<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e34d7oyji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e34d7oyji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:turtle-filled" {...props}></Icon>
