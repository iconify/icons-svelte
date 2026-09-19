<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzz3twymt.css';
import '../../css/p/p8lu4nblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rzz3twymt"/><path class="p8lu4nblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:volume-muted-fill-12" {...props}></Icon>
