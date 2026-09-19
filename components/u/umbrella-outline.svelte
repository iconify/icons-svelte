<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkp9uh0fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xkp9uh0fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:umbrella-outline" {...props}></Icon>
