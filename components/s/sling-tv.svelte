<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5u7ksb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5u7ksb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sling-tv" {...props}></Icon>
