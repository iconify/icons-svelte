<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktjsz9b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktjsz9b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:user-hard-hat" {...props}></Icon>
