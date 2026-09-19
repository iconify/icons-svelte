<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe4msz0hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe4msz0hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wind" {...props}></Icon>
