<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9w8p9bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9w8p9bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trouser-line" {...props}></Icon>
