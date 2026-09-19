<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irsxgx7dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="irsxgx7dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:sync" {...props}></Icon>
