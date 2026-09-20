<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a41ck6p4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a41ck6p4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:seeding-filled" {...props}></Icon>
