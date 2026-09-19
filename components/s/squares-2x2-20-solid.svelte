<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc28kmb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lc28kmb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:squares-2x2-20-solid" {...props}></Icon>
