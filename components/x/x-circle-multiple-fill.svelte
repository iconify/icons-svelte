<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogz__r_fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ogz__r_fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:x-circle-multiple-fill" {...props}></Icon>
