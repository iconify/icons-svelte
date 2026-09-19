<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ualvnw05g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ualvnw05g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-parking" {...props}></Icon>
