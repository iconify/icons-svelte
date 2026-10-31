<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_1hm9bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_1hm9bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-chevrons-right-filled" {...props}></Icon>
