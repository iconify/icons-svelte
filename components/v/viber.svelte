<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3u07guut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="h3u07guut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:viber" {...props}></Icon>
