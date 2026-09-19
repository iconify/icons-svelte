<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw0wsk98j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tw0wsk98j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:trapezoid" {...props}></Icon>
