<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1ejgib4k.css';
import '../../css/g/grac-wbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q1ejgib4k"/><path class="grac-wbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:top-left" {...props}></Icon>
