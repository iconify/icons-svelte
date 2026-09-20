<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn1itiinb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn1itiinb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:servicemark" {...props}></Icon>
