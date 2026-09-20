<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgljb1bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgljb1bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:star-check" {...props}></Icon>
