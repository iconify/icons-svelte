<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbl53bb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbl53bb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:squares-subtract-filled" {...props}></Icon>
