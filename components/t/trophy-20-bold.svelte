<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-0zjwbkw.css';
import '../../css/a/a1clh2bdx.css';
import '../../css/n/nzfznobps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v-0zjwbkw"/><path class="a1clh2bdx"/><path class="nzfznobps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trophy-20-bold" {...props}></Icon>
