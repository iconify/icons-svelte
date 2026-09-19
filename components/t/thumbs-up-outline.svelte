<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oflno8b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oflno8b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:thumbs-up-outline" {...props}></Icon>
