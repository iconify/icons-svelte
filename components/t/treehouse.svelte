<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp05-dnsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp05-dnsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:treehouse" {...props}></Icon>
