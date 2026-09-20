<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsthg0bza.css';
import '../../css/p/pptl0qd1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gsthg0bza"/><path class="pptl0qd1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:school-science-dna" {...props}></Icon>
