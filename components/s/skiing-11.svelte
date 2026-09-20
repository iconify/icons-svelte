<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok5iyvbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ok5iyvbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:skiing-11" {...props}></Icon>
