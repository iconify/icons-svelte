<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk-lepk_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-lepk_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:unlink" {...props}></Icon>
