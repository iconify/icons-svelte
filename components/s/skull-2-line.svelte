<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieudju2hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieudju2hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skull-2-line" {...props}></Icon>
