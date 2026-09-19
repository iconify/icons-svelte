<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk41io1ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mk41io1ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:teddy-bear-solid" {...props}></Icon>
