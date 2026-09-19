<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty380eb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty380eb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:scale" {...props}></Icon>
