<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjo89vpyj.css';
import '../../css/l/lja1fl8ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="gjo89vpyj"/><path class="lja1fl8ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-data" {...props}></Icon>
