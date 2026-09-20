<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7arh5b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t7arh5b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stone-wall-with-battlement" {...props}></Icon>
