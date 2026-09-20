<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5g7d5bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w5g7d5bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:shuffleboard" {...props}></Icon>
