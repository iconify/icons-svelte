<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q30b9z0uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q30b9z0uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:truck-check" {...props}></Icon>
