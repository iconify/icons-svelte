<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-4hgcbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j-4hgcbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:schedule" {...props}></Icon>
