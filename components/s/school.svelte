<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6ls7qang.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6ls7qang"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:school" {...props}></Icon>
