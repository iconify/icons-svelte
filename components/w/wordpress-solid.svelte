<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g86umtbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g86umtbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:wordpress-solid" {...props}></Icon>
