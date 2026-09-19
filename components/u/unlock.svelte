<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2kvcqbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2kvcqbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:unlock" {...props}></Icon>
