<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb7ny-b9u.css';
import '../../css/y/yebjw07xb.css';
import '../../css/y/yf53kj02n.css';
import '../../css/w/w871p5tnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pb7ny-b9u"/><path class="yebjw07xb"/><path class="yf53kj02n"/><path class="w871p5tnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:runningshirt" {...props}></Icon>
