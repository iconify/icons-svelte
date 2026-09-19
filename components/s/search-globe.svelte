<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx9blzb3a.css';
import '../../css/i/iabrmvfcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mx9blzb3a"/><path class="iabrmvfcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-globe" {...props}></Icon>
