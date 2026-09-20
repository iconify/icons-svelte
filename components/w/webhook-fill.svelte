<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc4tjhmeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc4tjhmeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:webhook-fill" {...props}></Icon>
