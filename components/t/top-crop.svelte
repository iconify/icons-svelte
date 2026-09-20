<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyd0wpb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyd0wpb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:top-crop" {...props}></Icon>
