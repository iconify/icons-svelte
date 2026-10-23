<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtan3fbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtan3fbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ticket-plus" {...props}></Icon>
