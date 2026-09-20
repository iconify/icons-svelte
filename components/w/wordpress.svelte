<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc1h7abdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kc1h7abdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wordpress" {...props}></Icon>
