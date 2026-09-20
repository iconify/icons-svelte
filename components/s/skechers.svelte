<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smtdp5bbp.css';
import '../../css/i/i423b8lay.css';
import '../../css/p/plefd-99d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":445,"height":168};
const content = `<path class="smtdp5bbp"/><path class="i423b8lay"/><path class="plefd-99d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:skechers" {...props}></Icon>
