<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e82bg1ebl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e82bg1ebl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spotify-fill" {...props}></Icon>
