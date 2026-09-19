<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4oannbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f4oannbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:star-solid" {...props}></Icon>
