<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg419tbbu.css';
import '../../css/k/koi2gi6-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wg419tbbu"/><path class="koi2gi6-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:text-input" {...props}></Icon>
