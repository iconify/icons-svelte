<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldyatl2-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldyatl2-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:tumblr-logo" {...props}></Icon>
