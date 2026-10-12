<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brz56sb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brz56sb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:table-cells-split-filled" {...props}></Icon>
