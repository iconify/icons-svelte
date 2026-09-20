<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azf7pht0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azf7pht0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:temperature-plus" {...props}></Icon>
