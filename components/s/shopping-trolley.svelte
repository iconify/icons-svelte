<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwg0nbcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xwg0nbcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:shopping-trolley" {...props}></Icon>
