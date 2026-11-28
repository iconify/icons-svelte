<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vupxk1x1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vupxk1x1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:suitcase-lock" {...props}></Icon>
