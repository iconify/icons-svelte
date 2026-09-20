<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc922ob0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc922ob0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rye" {...props}></Icon>
