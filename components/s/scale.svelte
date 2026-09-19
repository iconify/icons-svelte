<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoskosbxd.css';
import '../../css/p/puyvfbckp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoskosbxd b"/><path class="b puyvfbckp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:scale" {...props}></Icon>
