<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-xue7lql.css';
import '../../css/r/rh9letwnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f-xue7lql"/><path class="rh9letwnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:volume-high-sharp" {...props}></Icon>
