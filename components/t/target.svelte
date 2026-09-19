<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mghf9sskg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mghf9sskg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:target" {...props}></Icon>
