<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu3ddzb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu3ddzb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:triangle-off" {...props}></Icon>
