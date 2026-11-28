<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aurab21qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aurab21qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:target-arrow-solid" {...props}></Icon>
