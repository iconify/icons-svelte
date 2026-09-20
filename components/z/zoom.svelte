<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ladfd1b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ladfd1b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:zoom" {...props}></Icon>
