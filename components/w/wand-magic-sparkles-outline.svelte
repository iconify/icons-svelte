<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rprrz39yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rprrz39yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:wand-magic-sparkles-outline" {...props}></Icon>
