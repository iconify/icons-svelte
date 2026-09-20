<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy-pseb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy-pseb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:seek-next" {...props}></Icon>
