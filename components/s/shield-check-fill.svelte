<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk-bc8b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-bc8b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shield-check-fill" {...props}></Icon>
