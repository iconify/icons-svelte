<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e7jeh7wes.css';
import '../../css/w/wh5qu1bjh.css';
import '../../css/x/x9h1xwfff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e7jeh7wes"/><path class="wh5qu1bjh"/><path class="x9h1xwfff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tombstone-duotone" {...props}></Icon>
