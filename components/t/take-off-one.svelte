<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlm0orbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qlm0orbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:take-off-one" {...props}></Icon>
