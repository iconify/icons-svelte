<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdl0eybov.css';
import '../../css/z/z1aoycclw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jdl0eybov"/><path class="z1aoycclw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:watchguard" {...props}></Icon>
