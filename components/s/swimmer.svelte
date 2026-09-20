<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4843keka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4843keka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:swimmer" {...props}></Icon>
