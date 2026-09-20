<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6uiwabmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g6uiwabmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:wallet" {...props}></Icon>
