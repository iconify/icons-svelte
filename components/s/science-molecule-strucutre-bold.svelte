<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-illub7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-illub7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:science-molecule-strucutre-bold" {...props}></Icon>
