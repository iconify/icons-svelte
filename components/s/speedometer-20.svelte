<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahflbbcgy.css';
import '../../css/t/twd90018l.css';
import '../../css/u/ut-54jgvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ahflbbcgy"/><path class="twd90018l"/><path class="ut-54jgvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speedometer-20" {...props}></Icon>
