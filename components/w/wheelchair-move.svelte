<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0fqe3bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="e0fqe3bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:wheelchair-move" {...props}></Icon>
