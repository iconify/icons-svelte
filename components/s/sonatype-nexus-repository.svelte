<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecphvhbrv.css';
import '../../css/b/bzxzk3bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ecphvhbrv"/><path class="bzxzk3bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sonatype-nexus-repository" {...props}></Icon>
