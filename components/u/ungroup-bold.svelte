<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdm667-fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bdm667-fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:ungroup-bold" {...props}></Icon>
