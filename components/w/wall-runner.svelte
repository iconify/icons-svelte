<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv-kjmf_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv-kjmf_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-runner" {...props}></Icon>
