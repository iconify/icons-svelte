<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl9aqubvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl9aqubvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sofa-heart" {...props}></Icon>
