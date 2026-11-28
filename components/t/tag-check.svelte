<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbkca8bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbkca8bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tag-check" {...props}></Icon>
