<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci-fgibqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ci-fgibqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-x-fill" {...props}></Icon>
