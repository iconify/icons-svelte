<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts5c0usmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts5c0usmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sheep-fill-round" {...props}></Icon>
