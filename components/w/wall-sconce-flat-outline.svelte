<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3__cabmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3__cabmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wall-sconce-flat-outline" {...props}></Icon>
