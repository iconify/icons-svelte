<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr_nq_b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nr_nq_b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:squares-below-rectangle" {...props}></Icon>
