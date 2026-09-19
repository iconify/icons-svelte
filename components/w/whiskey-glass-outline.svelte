<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz56o3bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz56o3bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:whiskey-glass-outline" {...props}></Icon>
