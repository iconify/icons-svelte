<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcd36nbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcd36nbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:trello" {...props}></Icon>
