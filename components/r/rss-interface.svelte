<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odhvtp87n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odhvtp87n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:rss-interface" {...props}></Icon>
