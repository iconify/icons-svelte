<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni8k4pbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni8k4pbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-x" {...props}></Icon>
