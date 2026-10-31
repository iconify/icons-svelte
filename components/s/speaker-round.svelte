<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csux-tsoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csux-tsoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:speaker-round" {...props}></Icon>
