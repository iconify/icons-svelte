<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw6l45h2h.css';
import '../../css/c/c89ohuy8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uw6l45h2h"/><path class="c89ohuy8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:zip-wire" {...props}></Icon>
