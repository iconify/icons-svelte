<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwoukbc5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwoukbc5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rstudio-ide" {...props}></Icon>
