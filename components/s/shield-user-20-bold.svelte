<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld3dvsbdz.css';
import '../../css/c/cvsu0tmol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ld3dvsbdz"/><path class="cvsu0tmol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-user-20-bold" {...props}></Icon>
