<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhav9abqv.css';
import '../../css/v/vr9pgqgei.css';
import '../../css/a/anr8_0bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bhav9abqv"/><path class="vr9pgqgei"/><path class="anr8_0bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sync-20-bold" {...props}></Icon>
