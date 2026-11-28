<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szdujlbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szdujlbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:strawberry" {...props}></Icon>
