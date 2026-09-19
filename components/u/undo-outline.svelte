<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdgfbyb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdgfbyb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:undo-outline" {...props}></Icon>
