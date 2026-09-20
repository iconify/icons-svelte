<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk-trub3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pk-trub3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-check-validate" {...props}></Icon>
