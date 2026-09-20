<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlk0loasq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlk0loasq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thermometer-probe" {...props}></Icon>
