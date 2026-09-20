<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqky6zbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqky6zbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scan" {...props}></Icon>
