<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa6as_vez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wa6as_vez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:square" {...props}></Icon>
