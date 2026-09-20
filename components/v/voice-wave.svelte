<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcl44gbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcl44gbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:voice-wave" {...props}></Icon>
