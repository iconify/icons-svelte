<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tshufsbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tshufsbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:triangle-16" {...props}></Icon>
