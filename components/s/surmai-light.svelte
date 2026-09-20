<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh6cjl76d.css';
import '../../css/f/fpmgnqbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jh6cjl76d"/><path class="fpmgnqbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:surmai-light" {...props}></Icon>
