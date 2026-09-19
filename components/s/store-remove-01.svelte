<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2yml2zvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2yml2zvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:store-remove-01" {...props}></Icon>
