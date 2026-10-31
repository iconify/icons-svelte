<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en9t1ybbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en9t1ybbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-align-right-bulk-round" {...props}></Icon>
