<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8io8zx6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8io8zx6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:squares-exclude" {...props}></Icon>
