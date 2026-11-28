<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq1jeab-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq1jeab-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:syringe-check" {...props}></Icon>
