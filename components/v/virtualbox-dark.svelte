<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8j5c3sho.css';
import '../../css/b/be5fe-z3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a8j5c3sho"/><path class="be5fe-z3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:virtualbox-dark" {...props}></Icon>
