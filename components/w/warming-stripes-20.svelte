<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frrc-qxwg.css';
import '../../css/h/hce5i4bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="frrc-qxwg"/><path class="hce5i4bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:warming-stripes-20" {...props}></Icon>
