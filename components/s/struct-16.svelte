<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyrd3-bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wyrd3-bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:struct-16" {...props}></Icon>
