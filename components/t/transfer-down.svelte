<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x12hh6b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x12hh6b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:transfer-down" {...props}></Icon>
