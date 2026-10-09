<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb1scqbmo.css';
import '../../css/a/aqncqbc6o.css';
import '../../css/i/iomwkbcdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hb1scqbmo"/><path class="aqncqbc6o"/><path class="iomwkbcdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:transformer-20" {...props}></Icon>
