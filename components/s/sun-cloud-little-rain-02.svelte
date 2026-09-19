<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l2v9ecctk.css';
import '../../css/c/cjfmk3bls.css';
import '../../css/x/x3xz6cc_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l2v9ecctk"/><path class="cjfmk3bls"/><path class="x3xz6cc_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sun-cloud-little-rain-02" {...props}></Icon>
