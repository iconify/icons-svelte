<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gihp7z99x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gihp7z99x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-f-thin" {...props}></Icon>
