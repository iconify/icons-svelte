<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0np4mbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0np4mbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:target-check" {...props}></Icon>
