<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5n0-tron.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5n0-tron"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:thumbtack-solid" {...props}></Icon>
