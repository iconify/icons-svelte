<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uabfcuuto.css';
import '../../css/p/pg0nswt9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uabfcuuto"/><path class="pg0nswt9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ski-lift-20-bold" {...props}></Icon>
