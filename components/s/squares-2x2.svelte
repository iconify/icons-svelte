<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iua_9vstk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iua_9vstk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:squares-2x2" {...props}></Icon>
