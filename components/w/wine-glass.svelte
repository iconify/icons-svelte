<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuojs56aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wuojs56aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:wine-glass" {...props}></Icon>
