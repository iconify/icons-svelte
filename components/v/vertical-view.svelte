<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq33zac2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qq33zac2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vertical-view" {...props}></Icon>
