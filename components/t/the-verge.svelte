<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxftx6b1l.css';
import '../../css/n/ncu40jb7n.css';
import '../../css/m/m6donjb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fxftx6b1l"/><path class="ncu40jb7n"/><path class="m6donjb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-verge" {...props}></Icon>
