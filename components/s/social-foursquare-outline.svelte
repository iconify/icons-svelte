<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc81c-b-o.css';
import '../../css/y/ymu2chbcz.css';
import '../../css/m/mvj4cdb7t.css';
import '../../css/t/t013kn23x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qc81c-b-o"/><path class="ymu2chbcz"/><path class="mvj4cdb7t"/><path class="t013kn23x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-foursquare-outline" {...props}></Icon>
