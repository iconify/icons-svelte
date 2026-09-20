<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4fiz0l4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4fiz0l4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-2-outline" {...props}></Icon>
