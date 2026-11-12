<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foo-6s4av.css';
import '../../css/e/epzlemb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="foo-6s4av"/><path class="epzlemb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wger" {...props}></Icon>
