<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjgp6ub7i.css';
import '../../css/e/epzlemb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjgp6ub7i"/><path class="epzlemb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wger" {...props}></Icon>
