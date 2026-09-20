<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyyxt6xhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wyyxt6xhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:search-solid" {...props}></Icon>
