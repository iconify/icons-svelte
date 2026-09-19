<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/demkhgwzh.css';
import '../../css/t/to1_2obdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="demkhgwzh"/><path class="to1_2obdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stop-outline-filled" {...props}></Icon>
