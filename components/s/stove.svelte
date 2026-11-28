<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6o5_008e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6o5_008e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:stove" {...props}></Icon>
