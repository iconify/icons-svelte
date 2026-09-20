<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifahunbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifahunbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shovel-pitchforks" {...props}></Icon>
