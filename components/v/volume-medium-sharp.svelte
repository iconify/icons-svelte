<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwr0ifb7o.css';
import '../../css/a/ahflddu7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uwr0ifb7o"/><path class="ahflddu7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:volume-medium-sharp" {...props}></Icon>
