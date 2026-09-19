<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-jdclmww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-jdclmww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:truck-clock-outline" {...props}></Icon>
