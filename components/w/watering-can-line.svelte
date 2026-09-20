<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6pjnfbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6pjnfbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:watering-can-line" {...props}></Icon>
