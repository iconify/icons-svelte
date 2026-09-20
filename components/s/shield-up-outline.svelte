<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vyeui5bue.css';
import '../../css/z/z-oz-abqg.css';
import '../../css/d/d7l4obrtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vyeui5bue"/><path class="z-oz-abqg"/><path clip-rule="evenodd" class="d7l4obrtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-up-outline" {...props}></Icon>
