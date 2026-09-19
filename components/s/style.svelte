<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k901lmb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k901lmb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:style" {...props}></Icon>
