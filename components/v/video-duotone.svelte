<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o74lg6b1j.css';
import '../../css/y/yfj7mgfcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o74lg6b1j"/><path class="yfj7mgfcc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:video-duotone" {...props}></Icon>
