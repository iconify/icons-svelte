<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt4qth8mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt4qth8mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-bag-minus-filled" {...props}></Icon>
