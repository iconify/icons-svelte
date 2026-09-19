<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h65tdvo6n.css';
import '../../css/o/o5a8bt7sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h65tdvo6n"/><path class="o5a8bt7sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:videos" {...props}></Icon>
