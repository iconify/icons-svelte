<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvoo8fzsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvoo8fzsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:stop" {...props}></Icon>
