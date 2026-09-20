<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulyx1nwsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulyx1nwsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:shikimori" {...props}></Icon>
