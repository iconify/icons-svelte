<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0jt62teq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o0jt62teq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:row-height-l-outline" {...props}></Icon>
