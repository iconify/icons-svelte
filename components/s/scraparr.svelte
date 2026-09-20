<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmllns1vc.css';
import '../../css/u/uqy1x4y0w.css';
import '../../css/d/d1kn0uj4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmllns1vc"/><path class="uqy1x4y0w"/><path class="d1kn0uj4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scraparr" {...props}></Icon>
