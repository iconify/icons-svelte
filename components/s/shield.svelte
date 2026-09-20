<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9aztl2nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g9aztl2nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:shield" {...props}></Icon>
