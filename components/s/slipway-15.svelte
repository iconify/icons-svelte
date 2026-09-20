<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aksfx28xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aksfx28xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:slipway-15" {...props}></Icon>
