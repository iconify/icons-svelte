<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxcsbubyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bxcsbubyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-20-solid" {...props}></Icon>
