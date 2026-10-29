<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou3j7yrzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou3j7yrzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:undo-2" {...props}></Icon>
