<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca6smfbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca6smfbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:smashingmagazine" {...props}></Icon>
