<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlyg48kvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":614};
const content = `<path class="hlyg48kvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:safetygoggles" {...props}></Icon>
