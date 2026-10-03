<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9j6e4_4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9j6e4_4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:text-align-justify-center" {...props}></Icon>
