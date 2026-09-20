<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-b7uhibq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-b7uhibq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tuta" {...props}></Icon>
