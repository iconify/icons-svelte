<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3doeqbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2560,"height":1344};
const content = `<path class="n3doeqbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:timeslot-question" {...props}></Icon>
