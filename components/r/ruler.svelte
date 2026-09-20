<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm0j_5byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="cm0j_5byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:ruler" {...props}></Icon>
