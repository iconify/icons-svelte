<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6yhmzbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6yhmzbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:trophy-4" {...props}></Icon>
