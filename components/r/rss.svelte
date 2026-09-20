<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o33jmbc4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o33jmbc4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:rss" {...props}></Icon>
