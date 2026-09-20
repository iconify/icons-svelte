<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z6urhobix.css';
import '../../css/f/fu9c_kh2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="z6urhobix"/><path class="fu9c_kh2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:user-alt-3-duotone" {...props}></Icon>
