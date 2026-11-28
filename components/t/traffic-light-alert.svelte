<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adcbp-yaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adcbp-yaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:traffic-light-alert" {...props}></Icon>
