<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9xzdwbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1534,"height":1534};
const content = `<path class="q9xzdwbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wisetech-global" {...props}></Icon>
