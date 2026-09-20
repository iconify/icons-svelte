<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cht72sbxm.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/av3m8fbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGviYHfcjm" class="cht72sbxm"/></defs><g class="ft5dv1b6b"><use href="#SVGviYHfcjm"/><use href="#SVGviYHfcjm" class="av3m8fbrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tower-2" {...props}></Icon>
