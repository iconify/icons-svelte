<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy_gakbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy_gakbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:xbox" {...props}></Icon>
