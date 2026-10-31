<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yexscu63x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yexscu63x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-forward-round" {...props}></Icon>
