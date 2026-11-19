<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di7i0q5_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di7i0q5_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zendure-solarflow-2400-ac-plus" {...props}></Icon>
