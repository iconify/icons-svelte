<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwnocrufn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwnocrufn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:twitter-logo-1-solid" {...props}></Icon>
