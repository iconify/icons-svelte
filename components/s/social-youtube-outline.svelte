<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjqs9ia_t.css';
import '../../css/p/pofkdk1ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cjqs9ia_t"/><path class="pofkdk1ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-youtube-outline" {...props}></Icon>
