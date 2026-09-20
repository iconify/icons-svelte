<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_h8f4u0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_h8f4u0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smiley-excited" {...props}></Icon>
