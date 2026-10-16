<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu8m7-b_x.css';
import '../../css/y/ytutm3h1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uu8m7-b_x"/><path class="ytutm3h1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:siren-48" {...props}></Icon>
