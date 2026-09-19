<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4x1rhbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4x1rhbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:shield-solid" {...props}></Icon>
