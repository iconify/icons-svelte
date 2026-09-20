<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvq6x6b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvq6x6b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:singlestore" {...props}></Icon>
