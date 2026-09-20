<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgmc-yboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgmc-yboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:server4-filled" {...props}></Icon>
