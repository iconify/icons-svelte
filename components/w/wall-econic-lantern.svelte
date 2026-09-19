<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_a40-blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_a40-blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-econic-lantern" {...props}></Icon>
