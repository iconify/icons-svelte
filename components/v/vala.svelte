<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuucq2hxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuucq2hxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vala" {...props}></Icon>
