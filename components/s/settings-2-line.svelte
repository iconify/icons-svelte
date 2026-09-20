<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exa37_tip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exa37_tip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-2-line" {...props}></Icon>
