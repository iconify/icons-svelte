<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1hwcrbsr.css';
import '../../css/r/rdjvdkbbm.css';
import '../../css/e/e1fsegbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c1hwcrbsr"/><circle class="rdjvdkbbm"/><circle class="e1fsegbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-anonymous" {...props}></Icon>
