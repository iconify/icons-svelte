<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1-e4_6nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1-e4_6nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ship" {...props}></Icon>
