<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzm-m8l7i.css';
import '../../css/u/u-hzwbc2y.css';
import '../../css/a/aiwlnno1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zzm-m8l7i"/><path class="u-hzwbc2y"/><path class="aiwlnno1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-lock-20" {...props}></Icon>
