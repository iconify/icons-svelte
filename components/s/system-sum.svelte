<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/p/p1xl0obnf.css';
import '../../css/r/r_-y31b5j.css';
import '../../css/e/eac117bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="p1xl0obnf"/><path class="r_-y31b5j"/><path class="eac117bae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-sum" {...props}></Icon>
