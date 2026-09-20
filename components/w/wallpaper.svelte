<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k94e4mzcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k94e4mzcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallpaper" {...props}></Icon>
