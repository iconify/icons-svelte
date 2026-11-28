<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_iv6r6-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_iv6r6-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:video-call-x" {...props}></Icon>
