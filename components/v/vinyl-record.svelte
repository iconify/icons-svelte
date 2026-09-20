<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaurnylhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xaurnylhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vinyl-record" {...props}></Icon>
