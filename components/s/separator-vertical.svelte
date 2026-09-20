<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8262sblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8262sblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:separator-vertical" {...props}></Icon>
