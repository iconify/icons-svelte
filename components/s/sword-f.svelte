<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbtm6-bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2.5};
const content = `<path class="jbtm6-bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:sword-f" {...props}></Icon>
