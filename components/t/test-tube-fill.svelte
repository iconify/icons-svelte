<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fctqu-jjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fctqu-jjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:test-tube-fill" {...props}></Icon>
