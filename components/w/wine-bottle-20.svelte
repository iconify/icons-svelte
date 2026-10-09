<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdg210b0m.css';
import '../../css/y/yacgnsfyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mdg210b0m"/><path class="yacgnsfyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wine-bottle-20" {...props}></Icon>
