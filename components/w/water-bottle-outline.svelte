<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaohukb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaohukb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:water-bottle-outline" {...props}></Icon>
