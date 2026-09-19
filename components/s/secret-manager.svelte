<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4aqv5g7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4aqv5g7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:secret-manager" {...props}></Icon>
