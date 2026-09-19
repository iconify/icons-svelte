<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjzamabtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjzamabtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tablet" {...props}></Icon>
