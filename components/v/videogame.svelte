<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3mptb1ql.css';
import '../../css/h/hlumq0b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q3mptb1ql"/><path class="hlumq0b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:videogame" {...props}></Icon>
