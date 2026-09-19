<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/res45y0_a.css';
import '../../css/b/b-cf_z2lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="res45y0_a"/><path class="b-cf_z2lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:temp-high" {...props}></Icon>
