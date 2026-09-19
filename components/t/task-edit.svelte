<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puoncw33f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="puoncw33f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-edit" {...props}></Icon>
