<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdkv85ljh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdkv85ljh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tape-measure" {...props}></Icon>
