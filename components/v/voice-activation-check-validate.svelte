<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yktk2bixn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yktk2bixn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:voice-activation-check-validate" {...props}></Icon>
