<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwjy8pq2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwjy8pq2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:table-columns-split-filled" {...props}></Icon>
