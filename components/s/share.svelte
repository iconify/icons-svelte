<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abm-7gbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abm-7gbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:share" {...props}></Icon>
