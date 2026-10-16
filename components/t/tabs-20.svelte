<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhhiamiic.css';
import '../../css/e/efnhhmbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hhhiamiic"/><path class="efnhhmbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tabs-20" {...props}></Icon>
