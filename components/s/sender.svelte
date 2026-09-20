<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3x-gpp8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3x-gpp8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sender" {...props}></Icon>
