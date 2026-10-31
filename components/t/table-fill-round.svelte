<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfqqx6mhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfqqx6mhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-fill-round" {...props}></Icon>
