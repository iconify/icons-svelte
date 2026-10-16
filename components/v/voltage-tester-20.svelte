<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvi0cxbyw.css';
import '../../css/s/suxe2ovzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yvi0cxbyw"/><path class="suxe2ovzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-tester-20" {...props}></Icon>
