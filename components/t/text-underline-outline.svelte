<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilnoeuzqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilnoeuzqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:text-underline-outline" {...props}></Icon>
