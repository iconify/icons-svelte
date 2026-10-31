<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncp4okbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncp4okbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-minus-round" {...props}></Icon>
