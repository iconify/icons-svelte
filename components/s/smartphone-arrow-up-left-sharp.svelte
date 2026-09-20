<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojs3iy_9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojs3iy_9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:smartphone-arrow-up-left-sharp" {...props}></Icon>
