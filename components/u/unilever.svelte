<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knr_o8bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knr_o8bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:unilever" {...props}></Icon>
