<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hilrasb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hilrasb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:stroopwafel-solid" {...props}></Icon>
