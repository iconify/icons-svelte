<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br7fvbb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br7fvbb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vectorworks" {...props}></Icon>
