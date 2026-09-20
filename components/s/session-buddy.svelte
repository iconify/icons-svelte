<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipk4zab3u.css';
import '../../css/b/bgvnsfk4m.css';
import '../../css/s/s-2_26b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":65,"left":148,"top":164};
const content = `<path class="ipk4zab3u"/><path class="bgvnsfk4m"/><path class="s-2_26b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:session-buddy" {...props}></Icon>
