<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu5chmb3k.css';
import '../../css/s/s4xleyb5w.css';
import '../../css/l/l1pj3bg-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<rect class="wu5chmb3k"/><path class="s4xleyb5w"/><path class="l1pj3bg-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vuestorefront" {...props}></Icon>
