<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orig1-xyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orig1-xyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:router-round" {...props}></Icon>
