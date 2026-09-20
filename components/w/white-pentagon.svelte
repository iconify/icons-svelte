<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg5idf3sf.css';
import '../../css/v/vtcohfdfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="gg5idf3sf"/><path class="vtcohfdfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-pentagon" {...props}></Icon>
