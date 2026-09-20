<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6zbidbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p6zbidbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tag-with-peso" {...props}></Icon>
