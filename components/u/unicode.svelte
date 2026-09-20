<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq0rgdhov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oq0rgdhov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unicode" {...props}></Icon>
