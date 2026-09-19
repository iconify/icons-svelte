<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc8acmedn.css';
import '../../css/a/altk2-lbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc8acmedn"/><path class="altk2-lbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wind-storm" {...props}></Icon>
