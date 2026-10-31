<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph1k27nch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ph1k27nch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-letter-n-filled" {...props}></Icon>
