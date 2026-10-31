<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svlp0_bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svlp0_bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-x-filled" {...props}></Icon>
