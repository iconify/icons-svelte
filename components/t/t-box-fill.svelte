<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jatnfr4_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jatnfr4_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:t-box-fill" {...props}></Icon>
