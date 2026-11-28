<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugnncc1_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ugnncc1_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:telescope-fill" {...props}></Icon>
