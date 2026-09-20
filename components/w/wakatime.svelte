<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z2afm7wxp.css';
import '../../css/h/h63osy3wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":340,"height":340};
const content = `<g class="ft5dv1b6b"><path class="z2afm7wxp"/><path class="h63osy3wv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:wakatime" {...props}></Icon>
