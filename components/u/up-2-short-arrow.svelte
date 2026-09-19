<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka-7rw9rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka-7rw9rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:up-2-short-arrow" {...props}></Icon>
