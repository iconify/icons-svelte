<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myyy2316e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myyy2316e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:thanos" {...props}></Icon>
