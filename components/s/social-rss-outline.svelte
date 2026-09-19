<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm38_v6rc.css';
import '../../css/v/vvnu2369n.css';
import '../../css/b/bwfceobyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mm38_v6rc"/><path class="vvnu2369n"/><path class="bwfceobyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-rss-outline" {...props}></Icon>
