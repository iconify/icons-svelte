<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef_uqabxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ef_uqabxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-x-light" {...props}></Icon>
