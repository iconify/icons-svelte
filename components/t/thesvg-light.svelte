<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abcsioblf.css';
import '../../css/u/uc8haducx.css';
import '../../css/e/e01ksbcky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="abcsioblf"><path class="uc8haducx"/><path class="e01ksbcky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:thesvg-light" {...props}></Icon>
