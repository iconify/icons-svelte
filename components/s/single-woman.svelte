<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icnj0w2vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icnj0w2vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-woman" {...props}></Icon>
