<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5inhykbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5inhykbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:volume-low" {...props}></Icon>
