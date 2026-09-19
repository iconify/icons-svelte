<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us6p5c7zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us6p5c7zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:task-list" {...props}></Icon>
