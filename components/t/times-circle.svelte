<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8q7hs45s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8q7hs45s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:times-circle" {...props}></Icon>
