<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld8aljbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ld8aljbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-font-awesome" {...props}></Icon>
