<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv2k8ptcj.css';
import '../../css/d/d9yuvfbmn.css';
import '../../css/z/z3fjvlb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv2k8ptcj"/><path class="d9yuvfbmn"/><path class="z3fjvlb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:vault-light" {...props}></Icon>
