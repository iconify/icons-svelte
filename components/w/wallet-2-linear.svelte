<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nomdrxbld.css';
import '../../css/z/z8j9m1bjy.css';
import '../../css/z/zz8f-y99b.css';
import '../../css/t/t2jvb6bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nomdrxbld"/><path class="z8j9m1bjy"/><path class="zz8f-y99b"/><path class="t2jvb6bpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-2-linear" {...props}></Icon>
