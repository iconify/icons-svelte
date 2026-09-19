<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scxwqkb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scxwqkb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:toggle-left" {...props}></Icon>
