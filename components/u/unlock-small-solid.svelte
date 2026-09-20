<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avtxqwbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="avtxqwbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:unlock-small-solid" {...props}></Icon>
