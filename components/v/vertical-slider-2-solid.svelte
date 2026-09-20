<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihj4t_b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ihj4t_b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:vertical-slider-2-solid" {...props}></Icon>
