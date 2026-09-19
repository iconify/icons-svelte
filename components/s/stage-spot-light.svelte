<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj9q7uu1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj9q7uu1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:stage-spot-light" {...props}></Icon>
