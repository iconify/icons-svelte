<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6xx492kn.css';
import '../../css/x/xlyqlub7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b6xx492kn"/><path class="xlyqlub7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spillway-20" {...props}></Icon>
