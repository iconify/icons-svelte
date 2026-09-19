<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca34txrqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ca34txrqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sandwich" {...props}></Icon>
