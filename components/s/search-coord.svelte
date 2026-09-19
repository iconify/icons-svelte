<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lua0b7fsf.css';
import '../../css/a/aukm4obte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="lua0b7fsf"/><path class="aukm4obte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-coord" {...props}></Icon>
