<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpy6vikpy.css';
import '../../css/z/zsv18cbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpy6vikpy"/><path clip-rule="evenodd" class="zsv18cbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-vertical-minimalistic-bold" {...props}></Icon>
