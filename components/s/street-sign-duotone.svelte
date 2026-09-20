<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qvjsq0b9t.css';
import '../../css/y/yfiyrbfao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qvjsq0b9t"/><path class="yfiyrbfao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:street-sign-duotone" {...props}></Icon>
