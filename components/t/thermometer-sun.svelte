<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-pmo43tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-pmo43tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:thermometer-sun" {...props}></Icon>
