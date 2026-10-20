<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld3dvsbdz.css';
import '../../css/p/pudna3b6q.css';
import '../../css/a/a-axxkxuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ld3dvsbdz"/><path class="pudna3b6q"/><path class="a-axxkxuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-lock-20-bold" {...props}></Icon>
