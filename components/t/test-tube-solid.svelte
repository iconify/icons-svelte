<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rki2gpn-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rki2gpn-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:test-tube-solid" {...props}></Icon>
