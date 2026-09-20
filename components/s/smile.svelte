<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvffxab-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zvffxab-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:smile" {...props}></Icon>
