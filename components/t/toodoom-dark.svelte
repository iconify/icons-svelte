<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jau4w9qqu.css';
import '../../css/u/u3k9wcbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jau4w9qqu"/><path class="u3k9wcbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:toodoom-dark" {...props}></Icon>
