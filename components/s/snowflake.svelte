<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k17_obbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k17_obbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:snowflake" {...props}></Icon>
