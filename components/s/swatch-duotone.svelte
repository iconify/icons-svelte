<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/afaehbegj.css';
import '../../css/i/i75llfsmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="afaehbegj"/><path class="i75llfsmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:swatch-duotone" {...props}></Icon>
