<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxgx8jbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wxgx8jbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-2-outline" {...props}></Icon>
