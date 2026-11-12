<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi7c8xbbv.css';
import '../../css/b/b8j05vb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oi7c8xbbv"/><path class="b8j05vb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xbox-game-pass" {...props}></Icon>
