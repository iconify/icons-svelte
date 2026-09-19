<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plwpeyfet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plwpeyfet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:triple-wall-switch" {...props}></Icon>
