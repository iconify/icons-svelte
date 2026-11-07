<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1ku6jbdn.css';
import '../../css/j/j18sckbld.css';
import '../../css/y/yqonk1mgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l1ku6jbdn"/><path class="j18sckbld"/><path class="yqonk1mgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-vertical-minimalistic-outline" {...props}></Icon>
