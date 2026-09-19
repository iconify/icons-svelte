<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr2b31b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr2b31b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:shuffle-outline" {...props}></Icon>
