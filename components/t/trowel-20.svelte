<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgd5ds6is.css';
import '../../css/i/i1nkquj9v.css';
import '../../css/u/u9bld2bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zgd5ds6is"/><path class="i1nkquj9v"/><path class="u9bld2bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trowel-20" {...props}></Icon>
