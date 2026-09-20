<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfy2zropo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pfy2zropo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:table-tennis" {...props}></Icon>
