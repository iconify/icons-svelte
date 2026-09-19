<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftzkzib_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftzkzib_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:shrimp-solid" {...props}></Icon>
