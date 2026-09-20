<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq8_gvx6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq8_gvx6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zerodha" {...props}></Icon>
