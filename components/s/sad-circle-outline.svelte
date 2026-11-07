<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/che3aw1ld.css';
import '../../css/v/vu18-_bab.css';
import '../../css/l/lg9shfpyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="che3aw1ld"/><path class="vu18-_bab"/><path class="lg9shfpyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sad-circle-outline" {...props}></Icon>
