<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z414etblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z414etblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:shovel-dig" {...props}></Icon>
