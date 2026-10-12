<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7_paragx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7_paragx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tool-case-filled" {...props}></Icon>
