<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyd4a7czl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyd4a7czl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:thymeleaf" {...props}></Icon>
