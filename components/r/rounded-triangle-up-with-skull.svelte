<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf3qfuaba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uf3qfuaba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-up-with-skull" {...props}></Icon>
