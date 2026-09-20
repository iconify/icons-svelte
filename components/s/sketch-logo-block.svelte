<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cutibeb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cutibeb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:sketch-logo-block" {...props}></Icon>
