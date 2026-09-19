<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avisxtbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="avisxtbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sunshine-26" {...props}></Icon>
