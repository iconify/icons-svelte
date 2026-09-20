<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci5j7wbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ci5j7wbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:texas" {...props}></Icon>
