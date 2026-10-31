<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw3_31rij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw3_31rij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-info-fill-round" {...props}></Icon>
