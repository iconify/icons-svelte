<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srm6rdpdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srm6rdpdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-transfer-h" {...props}></Icon>
