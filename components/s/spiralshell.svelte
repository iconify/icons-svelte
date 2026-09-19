<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufom-nbao.css';
import '../../css/n/nm31ulbpm.css';
import '../../css/c/cfg6-7biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ufom-nbao"/><path class="nm31ulbpm"/><path class="cfg6-7biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:spiralshell" {...props}></Icon>
