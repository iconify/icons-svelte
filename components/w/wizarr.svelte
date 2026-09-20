<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn0wiolsr.css';
import '../../css/b/bcj4m3bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="wn0wiolsr"/><path class="bcj4m3bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wizarr" {...props}></Icon>
