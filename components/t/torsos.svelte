<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okph2cb0o.css';
import '../../css/r/r-cemmhlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="okph2cb0o"/><path class="r-cemmhlw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:torsos" {...props}></Icon>
