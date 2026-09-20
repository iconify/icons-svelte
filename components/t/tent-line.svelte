<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5lhf0b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5lhf0b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tent-line" {...props}></Icon>
