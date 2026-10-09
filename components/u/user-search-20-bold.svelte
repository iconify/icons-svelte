<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nehc85b4d.css';
import '../../css/g/gjporh8py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nehc85b4d"/><path class="gjporh8py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-search-20-bold" {...props}></Icon>
