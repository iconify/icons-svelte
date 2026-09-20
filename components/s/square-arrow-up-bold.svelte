<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st1-uurhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="st1-uurhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-arrow-up-bold" {...props}></Icon>
