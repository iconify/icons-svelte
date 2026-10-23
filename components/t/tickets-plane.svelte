<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t92-nacuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t92-nacuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tickets-plane" {...props}></Icon>
