<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjxj6dbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjxj6dbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:speaker-plus" {...props}></Icon>
