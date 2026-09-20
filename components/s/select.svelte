<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ra17bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9ra17bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:select" {...props}></Icon>
