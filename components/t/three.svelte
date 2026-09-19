<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxhi8gm6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yxhi8gm6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:three" {...props}></Icon>
