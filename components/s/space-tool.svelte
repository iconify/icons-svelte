<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2ljqbzto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="r2ljqbzto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:space-tool" {...props}></Icon>
