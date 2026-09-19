<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciwwc7f0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="ciwwc7f0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:surprise" {...props}></Icon>
