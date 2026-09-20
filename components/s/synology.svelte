<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak0bvlpdn.css';
import '../../css/k/k8lgery7w.css';
import '../../css/z/zixffebzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ak0bvlpdn"/><path class="k8lgery7w"/><path class="zixffebzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:synology" {...props}></Icon>
