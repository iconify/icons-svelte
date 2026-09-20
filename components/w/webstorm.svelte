<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mad1ojq5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mad1ojq5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:webstorm" {...props}></Icon>
