<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z182-6axt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z182-6axt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:self-hosted-show-dark" {...props}></Icon>
