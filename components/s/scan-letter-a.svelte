<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezw_7jbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezw_7jbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:scan-letter-a" {...props}></Icon>
