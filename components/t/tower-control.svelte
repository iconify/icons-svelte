<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejhcw39mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejhcw39mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:tower-control" {...props}></Icon>
