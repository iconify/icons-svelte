<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncnz8jeoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncnz8jeoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:squares-intersect" {...props}></Icon>
