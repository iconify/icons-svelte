<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr92k7byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr92k7byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:triangle" {...props}></Icon>
