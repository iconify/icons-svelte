<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ealdmy0gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ealdmy0gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:timescale" {...props}></Icon>
