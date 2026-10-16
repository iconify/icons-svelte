<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_a0sffvb.css';
import '../../css/f/fan1dzboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b_a0sffvb"/><path class="fan1dzboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tabs-20-bold" {...props}></Icon>
