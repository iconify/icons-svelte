<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz7n-pn_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uz7n-pn_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:xamarin-wordmark" {...props}></Icon>
