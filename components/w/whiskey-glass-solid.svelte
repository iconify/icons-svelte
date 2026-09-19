<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6_rnobfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6_rnobfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:whiskey-glass-solid" {...props}></Icon>
