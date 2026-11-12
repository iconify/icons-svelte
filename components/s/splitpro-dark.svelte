<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxxgysbnp.css';
import '../../css/p/pn9m9wb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxxgysbnp"/><path class="pn9m9wb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:splitpro-dark" {...props}></Icon>
