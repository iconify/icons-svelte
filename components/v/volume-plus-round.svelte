<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2-__6b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2-__6b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-plus-round" {...props}></Icon>
