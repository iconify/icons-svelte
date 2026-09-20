<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwof7pjvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwof7pjvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-dollar" {...props}></Icon>
