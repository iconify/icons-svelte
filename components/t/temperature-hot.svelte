<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay6-3hbyq.css';
import '../../css/y/ymie1nvqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ay6-3hbyq"/><path class="ymie1nvqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:temperature-hot" {...props}></Icon>
