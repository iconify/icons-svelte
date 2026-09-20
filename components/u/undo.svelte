<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_s3ipqpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p_s3ipqpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:undo" {...props}></Icon>
