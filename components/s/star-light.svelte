<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex9foacxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex9foacxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:star-light" {...props}></Icon>
