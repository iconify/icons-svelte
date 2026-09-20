<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuylrmdit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuylrmdit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stack-3-filled" {...props}></Icon>
