<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axzo35bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axzo35bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:studen-circle-network-logo-block" {...props}></Icon>
