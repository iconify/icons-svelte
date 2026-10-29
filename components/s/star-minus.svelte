<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv5n7ubdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv5n7ubdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:star-minus" {...props}></Icon>
