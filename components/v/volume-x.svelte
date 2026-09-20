<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5o_dob7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5o_dob7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:volume-x" {...props}></Icon>
