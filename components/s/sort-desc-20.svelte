<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh02dzb5a.css';
import '../../css/u/ufrf-lbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rh02dzb5a"/><path class="ufrf-lbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-desc-20" {...props}></Icon>
