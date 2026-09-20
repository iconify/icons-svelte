<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma83kwbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ma83kwbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonatype-nexus-repository-dark" {...props}></Icon>
