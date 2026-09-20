<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oln8vpg8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oln8vpg8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:thumbtack-outline" {...props}></Icon>
