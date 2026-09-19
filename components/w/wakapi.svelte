<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayy9uee8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayy9uee8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wakapi" {...props}></Icon>
