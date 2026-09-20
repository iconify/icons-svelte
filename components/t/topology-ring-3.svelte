<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjub1141u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjub1141u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-ring-3" {...props}></Icon>
