<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqp9l5bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tqp9l5bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:table-col-delete" {...props}></Icon>
