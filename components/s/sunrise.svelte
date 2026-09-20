<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2fnftbaj.css';
import '../../css/u/u92ri5qvj.css';
import '../../css/p/pa7le0b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2fnftbaj"/><path clip-rule="evenodd" class="u92ri5qvj"/><path class="pa7le0b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sunrise" {...props}></Icon>
