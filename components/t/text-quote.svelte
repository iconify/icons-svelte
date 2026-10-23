<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-qtgu_hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-qtgu_hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-quote" {...props}></Icon>
