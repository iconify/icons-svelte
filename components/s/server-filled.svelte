<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s91kl0bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s91kl0bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:server-filled" {...props}></Icon>
