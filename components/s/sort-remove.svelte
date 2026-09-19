<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5f48ybqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h5f48ybqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sort-remove" {...props}></Icon>
