<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjpbhobfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjpbhobfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:truecommand-light" {...props}></Icon>
