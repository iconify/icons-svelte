<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukrge3umx.css';
import '../../css/y/ybpm01_ag.css';
import '../../css/z/zo-06kn-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ukrge3umx"/><path class="ybpm01_ag"/><path class="zo-06kn-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-lock-20" {...props}></Icon>
