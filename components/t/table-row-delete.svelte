<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp_j_6pys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sp_j_6pys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:table-row-delete" {...props}></Icon>
