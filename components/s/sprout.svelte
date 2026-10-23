<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgv9fobbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgv9fobbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sprout" {...props}></Icon>
