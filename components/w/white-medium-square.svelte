<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i43r0eb1n.css';
import '../../css/y/y3rmrqmdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="i43r0eb1n"/><path class="y3rmrqmdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-medium-square" {...props}></Icon>
