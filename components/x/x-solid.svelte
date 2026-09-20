<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv2ni7q9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="dv2ni7q9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:x-solid" {...props}></Icon>
