<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z792yubyf.css';
import '../../css/g/gpbvbidrc.css';
import '../../css/j/jjet8kudg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":221};
const content = `<path class="z792yubyf"/><path class="gpbvbidrc"/><path class="jjet8kudg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vue" {...props}></Icon>
