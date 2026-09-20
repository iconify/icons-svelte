<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2686umpn.css';
import '../../css/v/v4ezc_mia.css';
import '../../css/y/ycs9ylboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2686umpn"/><path class="v4ezc_mia"/><path class="ycs9ylboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:statamic" {...props}></Icon>
