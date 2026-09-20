<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bal25inyd.css';
import '../../css/d/d1kdlidso.css';
import '../../css/i/itkrzdlol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bal25inyd"/><path class="d1kdlidso"/><path class="itkrzdlol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tablet" {...props}></Icon>
