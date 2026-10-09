<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjozgk1xh.css';
import '../../css/v/vfyr6kgzz.css';
import '../../css/w/w-aohegfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cjozgk1xh"/><path class="vfyr6kgzz"/><path class="w-aohegfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stadium-20-bold" {...props}></Icon>
