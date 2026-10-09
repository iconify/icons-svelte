<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4a-q3f0p.css';
import '../../css/z/zzw9zuasg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b4a-q3f0p"/><path class="zzw9zuasg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tariff-20-bold" {...props}></Icon>
