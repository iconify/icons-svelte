<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edc_msbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="edc_msbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:signpost-split-fill" {...props}></Icon>
