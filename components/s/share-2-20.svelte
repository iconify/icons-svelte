<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu29sma9m.css';
import '../../css/y/y8de8nbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lu29sma9m"/><path class="y8de8nbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:share-2-20" {...props}></Icon>
