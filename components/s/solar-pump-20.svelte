<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoon22kar.css';
import '../../css/m/m-kckroos.css';
import '../../css/q/q1lth85bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eoon22kar"/><path class="m-kckroos"/><path class="q1lth85bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-pump-20" {...props}></Icon>
