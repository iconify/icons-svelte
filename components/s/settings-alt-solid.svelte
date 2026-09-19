<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0lpc6lrj.css';
import '../../css/w/wj027_bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0lpc6lrj"/><path clip-rule="evenodd" class="wj027_bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:settings-alt-solid" {...props}></Icon>
