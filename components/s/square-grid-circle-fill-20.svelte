<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s47ll6kkm.css';
import '../../css/j/j-aqdhbtt.css';
import '../../css/j/jgh0owb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s47ll6kkm"/><path class="j-aqdhbtt"/><path class="jgh0owb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:square-grid-circle-fill-20" {...props}></Icon>
