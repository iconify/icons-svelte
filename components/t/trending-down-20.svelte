<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhczfhb2e.css';
import '../../css/c/clf6f0bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lhczfhb2e"/><path class="clf6f0bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trending-down-20" {...props}></Icon>
