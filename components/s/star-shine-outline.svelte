<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us0-41abq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="us0-41abq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-shine-outline" {...props}></Icon>
