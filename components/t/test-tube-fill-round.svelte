<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u07sl8b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u07sl8b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:test-tube-fill-round" {...props}></Icon>
