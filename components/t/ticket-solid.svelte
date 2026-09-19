<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymdz2acqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymdz2acqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:ticket-solid" {...props}></Icon>
