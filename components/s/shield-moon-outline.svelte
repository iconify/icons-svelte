<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asi4edbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asi4edbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-moon-outline" {...props}></Icon>
