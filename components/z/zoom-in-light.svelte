<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt0ma64ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt0ma64ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:zoom-in-light" {...props}></Icon>
