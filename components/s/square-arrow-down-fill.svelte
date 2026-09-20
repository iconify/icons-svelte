<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kslszo2im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kslszo2im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-down-fill" {...props}></Icon>
