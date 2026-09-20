<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfh6zxbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfh6zxbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zerotier" {...props}></Icon>
