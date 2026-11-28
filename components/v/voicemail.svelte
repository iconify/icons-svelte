<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb62anb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb62anb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:voicemail" {...props}></Icon>
