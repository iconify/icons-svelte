<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlkje40co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlkje40co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wheelchair-fill" {...props}></Icon>
