<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3g3o-fjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3g3o-fjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:star" {...props}></Icon>
