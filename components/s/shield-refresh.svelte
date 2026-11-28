<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeizt39os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeizt39os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:shield-refresh" {...props}></Icon>
