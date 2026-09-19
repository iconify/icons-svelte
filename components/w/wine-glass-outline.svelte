<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj572-jhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj572-jhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:wine-glass-outline" {...props}></Icon>
