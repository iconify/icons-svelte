<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4-2-ubeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="n4-2-ubeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:user-x" {...props}></Icon>
