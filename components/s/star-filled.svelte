<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tetjp7m-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tetjp7m-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:star-filled" {...props}></Icon>
