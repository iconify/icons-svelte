<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so_zjqcjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so_zjqcjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-align-start" {...props}></Icon>
