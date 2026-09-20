<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iebv6s_is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iebv6s_is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:temperature-empty" {...props}></Icon>
