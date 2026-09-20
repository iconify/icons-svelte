<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrhf55bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrhf55bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:trash-alt-solid" {...props}></Icon>
