<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8naaabxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8naaabxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-arrow-out-down-left" {...props}></Icon>
