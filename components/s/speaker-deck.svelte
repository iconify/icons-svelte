<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc-qm3iru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tc-qm3iru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:speaker-deck" {...props}></Icon>
