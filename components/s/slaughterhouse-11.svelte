<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuz81zbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="vuz81zbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:slaughterhouse-11" {...props}></Icon>
