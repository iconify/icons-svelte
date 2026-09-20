<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ypjs4tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3ypjs4tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wacme" {...props}></Icon>
