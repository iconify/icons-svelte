<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gef5ck7od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gef5ck7od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:twitter-fill" {...props}></Icon>
