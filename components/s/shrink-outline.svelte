<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0slkfbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0slkfbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:shrink-outline" {...props}></Icon>
