<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p80pbabhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p80pbabhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:smartwatch-round" {...props}></Icon>
