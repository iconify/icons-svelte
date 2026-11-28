<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngt-l5hup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ngt-l5hup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:turtle-bold" {...props}></Icon>
