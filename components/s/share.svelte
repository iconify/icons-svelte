<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1y3p2mzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1y3p2mzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:share" {...props}></Icon>
