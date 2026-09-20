<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlv6odb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlv6odb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sitemap" {...props}></Icon>
