<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqfz1qjfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqfz1qjfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:warehouse-fill-round" {...props}></Icon>
