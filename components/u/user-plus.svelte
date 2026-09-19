<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0lhoibac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d0lhoibac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:user-plus" {...props}></Icon>
