<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cis5txmal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cis5txmal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:transfer-h-filled" {...props}></Icon>
