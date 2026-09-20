<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfks5kbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfks5kbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sack-percent" {...props}></Icon>
