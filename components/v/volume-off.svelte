<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy980mv1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sy980mv1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:volume-off" {...props}></Icon>
